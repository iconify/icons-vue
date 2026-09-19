<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k31tkyekc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k31tkyekc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bad-two" /></template>
