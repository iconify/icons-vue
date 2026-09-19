<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uav2am_-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uav2am_-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hand-raised-slash-fill" /></template>
