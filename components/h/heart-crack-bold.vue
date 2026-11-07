<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oey6ny_di.css';
import '../../css/u/uv5m79ypg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oey6ny_di"/><path class="uv5m79ypg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-crack-bold" /></template>
