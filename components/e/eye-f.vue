<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzeek6plg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="mzeek6plg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:eye-f" /></template>
