<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc52_9a4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rc52_9a4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-list-box" /></template>
