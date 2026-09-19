<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jswgxzn3t.css';
import '../../css/q/qmn4-21rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jswgxzn3t"/><path class="qmn4-21rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:battery-3" /></template>
