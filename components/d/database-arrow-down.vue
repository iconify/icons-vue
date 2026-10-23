<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ima60vbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ima60vbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:database-arrow-down" /></template>
