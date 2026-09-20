<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz7-v-bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz7-v-bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:angle-up-light" /></template>
