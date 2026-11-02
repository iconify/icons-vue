<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjxcwxqyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjxcwxqyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bowl-line" /></template>
