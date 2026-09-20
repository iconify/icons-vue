<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjulmd4st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjulmd4st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-shield-2-line" /></template>
