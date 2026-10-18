<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0v_c7zwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0v_c7zwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:logs" /></template>
