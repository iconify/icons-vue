<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7m3mebqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7m3mebqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gift" /></template>
