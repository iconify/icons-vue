<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukhh2zsnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ukhh2zsnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-zoom-out-bold" /></template>
