<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/borjcccry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="borjcccry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:focus" /></template>
