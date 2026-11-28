<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj2248f8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj2248f8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:jar-x" /></template>
