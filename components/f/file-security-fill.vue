<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4gm5vbqz.css';
import '../../css/j/jw4xvqyjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4gm5vbqz"/><path class="jw4xvqyjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-security-fill" /></template>
