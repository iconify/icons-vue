<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq-jsy6wg.css';
import '../../css/d/dqwchbbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq-jsy6wg"/><path class="dqwchbbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:analysis" /></template>
