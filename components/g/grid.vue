<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnzy3dblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lnzy3dblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:grid" /></template>
