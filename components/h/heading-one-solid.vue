<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qejalnb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qejalnb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heading-one-solid" /></template>
