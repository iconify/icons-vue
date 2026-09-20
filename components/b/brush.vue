<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0opfxbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g0opfxbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:brush" /></template>
