<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb21tnwxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fb21tnwxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:group-23-solid" /></template>
