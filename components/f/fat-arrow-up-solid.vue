<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jydqubbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jydqubbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-arrow-up-solid" /></template>
