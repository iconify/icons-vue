<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3zb93bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3zb93bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-circle" /></template>
