<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aro6q6poa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aro6q6poa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-2-fill" /></template>
