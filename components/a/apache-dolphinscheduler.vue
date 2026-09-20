<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no4anzb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no4anzb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:apache-dolphinscheduler" /></template>
