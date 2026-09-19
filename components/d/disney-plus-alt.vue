<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t15ldcb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t15ldcb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:disney-plus-alt" /></template>
