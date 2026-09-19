<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clx1tcc9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="clx1tcc9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:briefcase-medical" /></template>
