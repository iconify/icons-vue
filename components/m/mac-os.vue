<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz_ly2pcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="gz_ly2pcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:mac-os" /></template>
