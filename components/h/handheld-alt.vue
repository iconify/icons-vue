<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0mq3zi8m.css';
import '../../css/j/jvh2qfzit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0mq3zi8m"/><path class="jvh2qfzit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:handheld-alt" /></template>
