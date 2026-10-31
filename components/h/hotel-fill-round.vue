<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs0d6y-st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs0d6y-st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hotel-fill-round" /></template>
