<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig8js3b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig8js3b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:bellring-on-outlined" /></template>
