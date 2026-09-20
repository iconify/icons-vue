<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svu7xeb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svu7xeb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:haystack" /></template>
