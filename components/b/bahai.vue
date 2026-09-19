<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmvz7vb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mmvz7vb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bahai" /></template>
