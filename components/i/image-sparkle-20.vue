<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7ntegbxz.css';
import '../../css/o/oav94mv2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x7ntegbxz"/><path class="oav94mv2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-sparkle-20" /></template>
