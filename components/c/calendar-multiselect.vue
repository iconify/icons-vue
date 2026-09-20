<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghz--5eim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghz--5eim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-multiselect" /></template>
