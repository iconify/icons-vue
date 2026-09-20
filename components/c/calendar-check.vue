<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl5h9i1sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl5h9i1sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-check" /></template>
