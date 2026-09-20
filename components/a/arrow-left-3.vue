<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a316u6-zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a316u6-zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left-3" /></template>
