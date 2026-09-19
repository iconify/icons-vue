<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-k5ynfvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="v-k5ynfvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:facebook-rect" /></template>
