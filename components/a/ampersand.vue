<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-o6htbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-o6htbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ampersand" /></template>
