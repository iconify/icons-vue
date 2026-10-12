<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pca152bqg.css';
import '../../css/f/fdgucpbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pca152bqg"/><path class="fdgucpbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:battery-full-filled" /></template>
