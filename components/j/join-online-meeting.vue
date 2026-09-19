<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jns9x8bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jns9x8bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:join-online-meeting" /></template>
