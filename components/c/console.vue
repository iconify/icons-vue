<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-kiu1bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-kiu1bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:console" /></template>
