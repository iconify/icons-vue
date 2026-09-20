<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjs4o1qnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjs4o1qnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barbell-fill" /></template>
