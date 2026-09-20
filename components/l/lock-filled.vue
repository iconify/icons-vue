<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or-9nt8zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or-9nt8zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:lock-filled" /></template>
