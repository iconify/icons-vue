<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g03waw7_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g03waw7_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-plus-fill" /></template>
