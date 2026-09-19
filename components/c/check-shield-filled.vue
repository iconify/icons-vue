<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv34kebtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv34kebtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:check-shield-filled" /></template>
