<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiu7ubcyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiu7ubcyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:go-group" /></template>
