<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2ib5fbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2ib5fbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-edit-outline" /></template>
