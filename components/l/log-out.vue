<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2-0v_biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2-0v_biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:log-out" /></template>
