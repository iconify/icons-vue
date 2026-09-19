<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9vd2w9_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1792};
const content = `<path class="p9vd2w9_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:building" /></template>
