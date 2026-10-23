<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfe2m2bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfe2m2bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:can-soda" /></template>
