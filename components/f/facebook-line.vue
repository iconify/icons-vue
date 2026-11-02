<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7q9k5bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7q9k5bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:facebook-line" /></template>
