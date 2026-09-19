<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diaukacrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="diaukacrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lamp" /></template>
