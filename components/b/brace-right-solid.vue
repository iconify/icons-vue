<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is9lt_wff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is9lt_wff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:brace-right-solid" /></template>
