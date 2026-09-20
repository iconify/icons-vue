<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq8sby3jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq8sby3jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gps-slash-filled" /></template>
