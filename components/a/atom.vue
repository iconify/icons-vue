<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh1l9-vtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":898,"height":1024};
const content = `<path class="dh1l9-vtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:atom" /></template>
