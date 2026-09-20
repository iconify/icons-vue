<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hryrjgebn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hryrjgebn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:angle-down" /></template>
