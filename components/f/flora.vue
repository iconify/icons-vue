<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0andfb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0andfb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:flora" /></template>
