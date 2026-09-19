<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6isdebeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6isdebeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:annotation-alert-filled" /></template>
