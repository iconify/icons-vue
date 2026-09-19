<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjpro_u9e.css';
import '../../css/q/q0wqs_b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xjpro_u9e"/><path class="q0wqs_b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:create-sharp" /></template>
