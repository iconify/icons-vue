<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqm39aclf.css';
import '../../css/t/tzb51cxjt.css';
import '../../css/e/epfj3sb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqm39aclf"/><path class="tzb51cxjt"/><path class="epfj3sb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:graph-bar" /></template>
