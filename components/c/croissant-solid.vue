<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_2z7ccnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_2z7ccnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:croissant-solid" /></template>
