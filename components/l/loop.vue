<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h04f6kb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h04f6kb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:loop" /></template>
