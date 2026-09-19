<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3r70jbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="h3r70jbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:american-express" /></template>
