<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch575kbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":488};
const content = `<path class="ch575kbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hyves" /></template>
