<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm2-wqytx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm2-wqytx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:calendar-slash" /></template>
