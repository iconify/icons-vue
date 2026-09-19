<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owpy5-7fq.css';
import '../../css/q/q6421ib4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="owpy5-7fq st1"/><path class="q6421ib4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gitea-wordmark" /></template>
