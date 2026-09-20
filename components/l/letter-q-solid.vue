<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8ag3311v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8ag3311v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-q-solid" /></template>
