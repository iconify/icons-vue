<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytv8j6l6t.css';
import '../../css/q/q5418bbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytv8j6l6t"/><path class="q5418bbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:check-circle" /></template>
