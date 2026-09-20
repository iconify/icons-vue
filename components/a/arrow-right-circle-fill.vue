<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xisg-gb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xisg-gb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-circle-fill" /></template>
