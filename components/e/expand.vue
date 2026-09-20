<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h61c-tcnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h61c-tcnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:expand" /></template>
