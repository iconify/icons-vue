<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f178wil9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f178wil9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-from-line" /></template>
