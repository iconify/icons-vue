<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nro_fcb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nro_fcb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:first-aid-kit" /></template>
