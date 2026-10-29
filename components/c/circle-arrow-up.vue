<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrsim2bww.css';
import '../../css/h/h7jt2xa4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yrsim2bww"/><path class="h7jt2xa4c wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:circle-arrow-up" /></template>
