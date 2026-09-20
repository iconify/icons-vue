<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as1j4ndtg.css';
import '../../css/q/qyo4u7bbg.css';
import '../../css/b/bc1hhwfbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="as1j4ndtg"/><path class="qyo4u7bbg"/><path class="bc1hhwfbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:goal-16" /></template>
