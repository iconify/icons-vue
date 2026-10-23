<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h948yl_8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h948yl_8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:galaxy" /></template>
