<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/embr9hbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="embr9hbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bread" /></template>
