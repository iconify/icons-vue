<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9bla539y.css';
import '../../css/q/qbfdzwb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9bla539y"/><path class="qbfdzwb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-down-to-line-outline" /></template>
