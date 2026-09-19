<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvv2sxohs.css';
import '../../css/t/txt750bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xvv2sxohs"/><path class="txt750bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:appwrite-wordmark" /></template>
