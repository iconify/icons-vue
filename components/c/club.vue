<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4uhf6e_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4uhf6e_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:club" /></template>
