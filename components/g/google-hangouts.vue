<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntzcl4b-u.css';
import '../../css/g/gjisevbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntzcl4b-u"/><path class="gjisevbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:google-hangouts" /></template>
