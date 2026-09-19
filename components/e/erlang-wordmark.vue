<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1w5x4bwa.css';
import '../../css/x/x46jw6bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="b1w5x4bwa"/><path class="x46jw6bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:erlang-wordmark" /></template>
