<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls4o5rx5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls4o5rx5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-to-line" /></template>
