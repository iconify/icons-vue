<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auabr42fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auabr42fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:code-light" /></template>
