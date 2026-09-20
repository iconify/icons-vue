<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brzibym8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brzibym8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-2" /></template>
