<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilic3tb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilic3tb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fatrows" /></template>
