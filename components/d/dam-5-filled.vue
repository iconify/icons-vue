<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1j1yutiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1j1yutiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dam-5-filled" /></template>
