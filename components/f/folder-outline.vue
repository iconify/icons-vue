<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc_9edazi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zc_9edazi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-outline" /></template>
