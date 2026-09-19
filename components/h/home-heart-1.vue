<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k797_m4st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k797_m4st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:home-heart-1" /></template>
