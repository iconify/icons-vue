<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xosd-cfuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xosd-cfuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-right-stop-light" /></template>
