<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6k-pbc_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="b6k-pbc_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hands-holding-circle" /></template>
