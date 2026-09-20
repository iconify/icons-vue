<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvsj4rbkk.css';
import '../../css/l/l5qz7fbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="yvsj4rbkk"/><path class="l5qz7fbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:compass-duotone" /></template>
