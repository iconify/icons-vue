<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opt-i29gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="opt-i29gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:circle-star-filled" /></template>
