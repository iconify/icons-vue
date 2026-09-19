<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqbnbtbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="dqbnbtbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin-tongue-squint" /></template>
