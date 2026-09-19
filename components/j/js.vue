<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abi5rp9im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="abi5rp9im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:js" /></template>
