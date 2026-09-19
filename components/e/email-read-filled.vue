<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq7etfk1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hq7etfk1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-read-filled" /></template>
