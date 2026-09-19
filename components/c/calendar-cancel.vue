<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc0__mb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bc0__mb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-cancel" /></template>
