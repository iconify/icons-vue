<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xndih1bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xndih1bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:asterisk-solid" /></template>
