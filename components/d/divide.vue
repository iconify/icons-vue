<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dun9wskug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dun9wskug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:divide" /></template>
