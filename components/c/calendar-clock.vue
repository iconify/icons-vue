<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtzkyibhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qtzkyibhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:calendar-clock" /></template>
