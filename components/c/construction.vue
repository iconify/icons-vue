<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm3s18ekn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gm3s18ekn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:construction" /></template>
