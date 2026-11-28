<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve0ei_2st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve0ei_2st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clock-play" /></template>
