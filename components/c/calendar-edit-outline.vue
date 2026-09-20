<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/argc_ccvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="argc_ccvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-edit-outline" /></template>
