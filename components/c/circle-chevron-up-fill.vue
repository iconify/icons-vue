<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4qntxb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4qntxb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-chevron-up-fill" /></template>
