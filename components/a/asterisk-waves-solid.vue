<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-tbgkzgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-tbgkzgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-waves-solid" /></template>
