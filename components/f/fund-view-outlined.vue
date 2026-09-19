<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5nzkvbsa.css';
import '../../css/b/bhztshb0g.css';
import '../../css/n/n1mj_5hgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o5nzkvbsa"/><path class="bhztshb0g"/><path class="n1mj_5hgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:fund-view-outlined" /></template>
