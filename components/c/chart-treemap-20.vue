<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svxkqfaev.css';
import '../../css/w/wxvl6gbzy.css';
import '../../css/k/ko9pd73aq.css';
import '../../css/c/c98cqvbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="svxkqfaev"/><path class="wxvl6gbzy"/><path class="ko9pd73aq"/><path class="c98cqvbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-treemap-20" /></template>
