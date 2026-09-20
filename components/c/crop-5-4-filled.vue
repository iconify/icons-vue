<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yztl9nsel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yztl9nsel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-5-4-filled" /></template>
