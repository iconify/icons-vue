<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l69rg0b1y.css';
import '../../css/f/f6ypmdp8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l69rg0b1y"/><path class="f6ypmdp8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gradient-filled" /></template>
