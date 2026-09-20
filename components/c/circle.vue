<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzsfz8ozm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzsfz8ozm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:circle" /></template>
