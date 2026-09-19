<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsrj86a-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="lsrj86a-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:home" /></template>
