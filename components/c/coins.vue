<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glh57ibmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="glh57ibmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:coins" /></template>
