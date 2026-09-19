<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1uq_ccag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f1uq_ccag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alarm-snooze-filled" /></template>
