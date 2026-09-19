<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu89hqblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu89hqblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:gift" /></template>
