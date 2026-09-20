<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvnl2-5op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wvnl2-5op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:briefcase-alt-outline" /></template>
