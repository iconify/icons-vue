<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzx5i9bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gzx5i9bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:j" /></template>
