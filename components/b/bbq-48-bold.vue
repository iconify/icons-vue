<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw-t5bcty.css';
import '../../css/d/dqolik5wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xw-t5bcty"/><path class="dqolik5wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bbq-48-bold" /></template>
