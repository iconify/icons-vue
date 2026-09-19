<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2oac6j-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1792};
const content = `<path class="g2oac6j-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:500px" /></template>
