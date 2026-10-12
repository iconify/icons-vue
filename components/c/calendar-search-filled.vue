<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ineotobot.css';
import '../../css/j/j9mguybwz.css';
import '../../css/g/gjba8cbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ineotobot"/><path clip-rule="evenodd" class="j9mguybwz"/><path class="gjba8cbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-search-filled" /></template>
