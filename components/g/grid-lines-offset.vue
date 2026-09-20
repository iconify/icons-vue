<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd0ufyboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd0ufyboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:grid-lines-offset" /></template>
