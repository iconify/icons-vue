<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewqxa-jut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ewqxa-jut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brightnesshalf" /></template>
