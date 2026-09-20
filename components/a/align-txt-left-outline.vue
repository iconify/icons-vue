<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaozv3mzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jaozv3mzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:align-txt-left-outline" /></template>
