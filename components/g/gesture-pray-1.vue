<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqb7zpojt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqb7zpojt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-pray-1" /></template>
