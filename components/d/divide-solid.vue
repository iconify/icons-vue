<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5cg0fb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5cg0fb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:divide-solid" /></template>
