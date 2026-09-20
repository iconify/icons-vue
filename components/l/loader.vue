<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj9dx5mvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj9dx5mvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:loader" /></template>
