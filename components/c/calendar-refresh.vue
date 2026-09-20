<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pus6_rbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pus6_rbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-refresh" /></template>
