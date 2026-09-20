<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db2z1jbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db2z1jbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-paragraph" /></template>
