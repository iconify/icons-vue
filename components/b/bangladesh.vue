<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeezzsgew.css';
import '../../css/l/lxcqcfbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="zeezzsgew"/><path class="lxcqcfbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:bangladesh" /></template>
