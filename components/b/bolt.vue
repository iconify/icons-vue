<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8xr0sedz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="b8xr0sedz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bolt" /></template>
