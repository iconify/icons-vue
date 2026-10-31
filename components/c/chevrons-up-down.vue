<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/dea1ln4ua.css';
import '../../css/t/tmivq76kq.css';
import '../../css/z/z0nui8bre.css';
import '../../css/u/u6rmc7cfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="dea1ln4ua wm-shadow"/><path class="tmivq76kq wm-shadow"/><path class="z0nui8bre"/><path class="u6rmc7cfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:chevrons-up-down" /></template>
