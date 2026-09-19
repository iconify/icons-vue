<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i335q_--m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="i335q_--m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:gbp" /></template>
