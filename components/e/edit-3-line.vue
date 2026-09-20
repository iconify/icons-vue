<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejwog5b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejwog5b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-3-line" /></template>
