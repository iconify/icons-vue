<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg5u9m4to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg5u9m4to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-arrow-down-sharp" /></template>
