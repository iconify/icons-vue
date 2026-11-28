<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uejpnu0db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uejpnu0db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:brace-left-solid" /></template>
