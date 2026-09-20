<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omgi_ocxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omgi_ocxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gerrit" /></template>
