<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrhj9hpeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrhj9hpeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:attachment" /></template>
