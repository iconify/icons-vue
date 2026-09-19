<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnk5bhbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="fnk5bhbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:lungs" /></template>
