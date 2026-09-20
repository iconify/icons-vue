<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g057fib1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g057fib1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-9-fill" /></template>
