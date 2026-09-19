<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtvztsq6v.css';
import '../../css/v/v-s_jsdhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtvztsq6v"/><path class="v-s_jsdhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:dollar" /></template>
