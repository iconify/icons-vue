<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae4p8ufye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae4p8ufye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:config-vertical" /></template>
