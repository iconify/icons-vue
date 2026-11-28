<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz7g6o3_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz7g6o3_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:eye-x" /></template>
