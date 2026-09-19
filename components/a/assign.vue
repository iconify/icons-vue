<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t51j7yp-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t51j7yp-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:assign" /></template>
