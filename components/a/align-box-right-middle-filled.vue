<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htg1gvych.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htg1gvych"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-right-middle-filled" /></template>
