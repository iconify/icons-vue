<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr72by21p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr72by21p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dreamcast" /></template>
