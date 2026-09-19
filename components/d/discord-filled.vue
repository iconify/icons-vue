<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifq7fr6yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ifq7fr6yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:discord-filled" /></template>
