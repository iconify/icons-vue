<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8qxwmb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d8qxwmb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:data-screen-filled" /></template>
