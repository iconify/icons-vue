<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvy2h7vyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xvy2h7vyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:distribute-vertical-solid" /></template>
