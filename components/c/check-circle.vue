<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtp0xqp4x.css';
import '../../css/j/j3n2vbcov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtp0xqp4x"/><path class="j3n2vbcov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:check-circle" /></template>
