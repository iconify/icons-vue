<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubm57g7cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubm57g7cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:attachment" /></template>
