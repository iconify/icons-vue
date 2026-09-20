<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0jg7abxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0jg7abxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-unlock" /></template>
