<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmlk55iho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmlk55iho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-fado" /></template>
