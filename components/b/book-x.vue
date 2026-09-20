<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3bve4cle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3bve4cle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-x" /></template>
