<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxxjieq7t.css';
import '../../css/l/lec3gmbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxxjieq7t"/><path class="lec3gmbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:calendar-days" /></template>
