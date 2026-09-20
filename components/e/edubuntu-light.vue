<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr68kubtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zr68kubtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:edubuntu-light" /></template>
