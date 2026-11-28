<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9iid9awd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9iid9awd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:accessibility-solid" /></template>
