<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnxf5iqlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":469,"height":512};
const content = `<path class="fnxf5iqlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ansible-alt" /></template>
