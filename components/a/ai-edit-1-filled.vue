<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3kjyubpd.css';
import '../../css/i/i67ob3bwq.css';
import '../../css/e/esgx7hbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3kjyubpd"/><path clip-rule="evenodd" class="i67ob3bwq"/><path class="esgx7hbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-edit-1-filled" /></template>
