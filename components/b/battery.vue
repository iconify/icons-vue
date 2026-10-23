<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2b2h7b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2b2h7b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery" /></template>
