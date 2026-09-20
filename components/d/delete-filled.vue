<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5rkeab4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5rkeab4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:delete-filled" /></template>
