<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo4ztu6st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo4ztu6st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-big-left" /></template>
