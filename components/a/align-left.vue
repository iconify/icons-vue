<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9upf7bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="v9upf7bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:align-left" /></template>
