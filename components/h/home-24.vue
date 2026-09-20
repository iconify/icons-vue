<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzjs4ubbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gzjs4ubbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:home-24" /></template>
