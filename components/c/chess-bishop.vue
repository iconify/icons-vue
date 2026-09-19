<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k544t6a1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="k544t6a1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chess-bishop" /></template>
