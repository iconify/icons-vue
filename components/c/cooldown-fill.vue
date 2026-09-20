<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kamhrtb5g.css';
import '../../css/l/l9ok9ouey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kamhrtb5g"/><path class="l9ok9ouey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cooldown-fill" /></template>
