<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lumyekqkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lumyekqkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:k3s" /></template>
