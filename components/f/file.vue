<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxp7l0bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxp7l0bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:file" /></template>
