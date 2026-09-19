<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wem_b1dpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wem_b1dpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:facebook-stroke-12" /></template>
