<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx2pj_bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yx2pj_bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-check-fill" /></template>
