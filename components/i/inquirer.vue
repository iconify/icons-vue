<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvradw0gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvradw0gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:inquirer" /></template>
