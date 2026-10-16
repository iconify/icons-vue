<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5g_98bjs.css';
import '../../css/i/ibk4nlb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s5g_98bjs"/><path class="ibk4nlb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:core-sample-48" /></template>
