<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo5dafbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo5dafbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-line" /></template>
