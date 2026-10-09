<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llvz37kzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="llvz37kzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hex-key-20" /></template>
