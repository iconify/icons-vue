<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug6f-tjsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug6f-tjsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:comment-error" /></template>
