<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taopki_li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taopki_li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:clock" /></template>
