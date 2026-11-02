<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jurw6yb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jurw6yb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chef-hat-fill" /></template>
