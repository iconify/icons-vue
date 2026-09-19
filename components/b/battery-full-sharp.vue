<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt57vq-0m.css';
import '../../css/z/zlx_zlb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wt57vq-0m"/><path class="zlx_zlb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:battery-full-sharp" /></template>
