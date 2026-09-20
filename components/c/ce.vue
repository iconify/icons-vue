<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o--zq9bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o--zq9bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ce" /></template>
