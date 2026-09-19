<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymujj4bpl.css';
import '../../css/q/qxpha_tbq.css';
import '../../css/f/fuhxmiogs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymujj4bpl"/><circle class="qxpha_tbq"/><path class="fuhxmiogs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-alert" /></template>
