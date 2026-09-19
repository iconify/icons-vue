<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llw355j1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="llw355j1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:google" /></template>
