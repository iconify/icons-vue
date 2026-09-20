<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im55vabao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="im55vabao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:leantime-dark" /></template>
