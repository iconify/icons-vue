<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwg_5dfby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwg_5dfby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:alarabiya-ch" /></template>
