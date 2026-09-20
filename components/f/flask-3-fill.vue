<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbdd1oz_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nbdd1oz_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-3-fill" /></template>
