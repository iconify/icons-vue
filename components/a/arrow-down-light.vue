<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vioi655bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vioi655bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-down-light" /></template>
