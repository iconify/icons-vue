<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuf5-ng-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuf5-ng-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:crop" /></template>
