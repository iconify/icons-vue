<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atyzbqqte.css';
import '../../css/l/lqtxhpbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="atyzbqqte"/><path class="lqtxhpbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ecto-wordmark" /></template>
