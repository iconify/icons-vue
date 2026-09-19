<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcgzi08rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":488};
const content = `<path class="kcgzi08rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:bebo" /></template>
