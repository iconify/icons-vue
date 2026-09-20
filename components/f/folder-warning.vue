<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg32c-tpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg32c-tpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-warning" /></template>
