<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x120vrb5q.css';
import '../../css/t/tl5abbc0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x120vrb5q"/><path class="tl5abbc0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:ansible-wordmark" /></template>
