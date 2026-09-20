<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0wtyze8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0wtyze8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layout-panel-bottom-solid" /></template>
