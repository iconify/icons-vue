<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql3a4ib0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql3a4ib0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-s-square-solid" /></template>
