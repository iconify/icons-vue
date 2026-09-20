<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhaw4ccch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhaw4ccch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-cancel-outline" /></template>
