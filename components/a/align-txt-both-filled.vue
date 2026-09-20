<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnd6xk9ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qnd6xk9ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:align-txt-both-filled" /></template>
