<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crjj_4lqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crjj_4lqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lantern-2-fill" /></template>
