<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxrv3d63f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxrv3d63f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-left-down-fill" /></template>
