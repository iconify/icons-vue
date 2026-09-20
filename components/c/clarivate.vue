<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6-1a3-st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6-1a3-st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:clarivate" /></template>
