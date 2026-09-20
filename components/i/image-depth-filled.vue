<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln2mrcb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln2mrcb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image-depth-filled" /></template>
