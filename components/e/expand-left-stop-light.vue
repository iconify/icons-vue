<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxl8m9b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxl8m9b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-left-stop-light" /></template>
