<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_d9kjclj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i_d9kjclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flintlock-pistol" /></template>
