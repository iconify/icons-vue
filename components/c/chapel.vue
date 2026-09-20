<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cesyobc_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cesyobc_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:chapel" /></template>
