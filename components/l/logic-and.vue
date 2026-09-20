<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw0t9gb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw0t9gb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:logic-and" /></template>
