<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhh05tb7v.css';
import '../../css/a/ayxx-hbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhh05tb7v"/><path class="ayxx-hbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:door-line" /></template>
