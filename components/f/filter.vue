<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9y8rv3iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g9y8rv3iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:filter" /></template>
