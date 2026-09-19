<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqo2otbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqo2otbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ear-slash" /></template>
