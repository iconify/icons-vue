<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfzlipmmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfzlipmmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lock-open-keyhole" /></template>
