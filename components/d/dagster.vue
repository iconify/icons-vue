<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y084-wbbv.css';
import '../../css/h/hvnqnlbmu.css';
import '../../css/j/js9j7cc9u.css';
import '../../css/b/bj-8yzcrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y084-wbbv"/><path class="hvnqnlbmu"/><path class="js9j7cc9u"/><path class="bj-8yzcrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dagster" /></template>
