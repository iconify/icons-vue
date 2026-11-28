<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1q2_6b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1q2_6b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-question" /></template>
