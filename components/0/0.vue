<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfs5vejnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nfs5vejnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:0" /></template>
