<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1ye1dzyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1ye1dzyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:align-left" /></template>
