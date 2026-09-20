<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvfc_ab5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvfc_ab5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid6-filled" /></template>
