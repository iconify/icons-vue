<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7wp6fi0u.css';
import '../../css/y/yze9w1b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7wp6fi0u"/><path class="yze9w1b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:laptop-code-solid" /></template>
