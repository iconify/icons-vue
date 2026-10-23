<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl4f5wabm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl4f5wabm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:factory" /></template>
