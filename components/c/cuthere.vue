<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_4vvvb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="x_4vvvb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cuthere" /></template>
