<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teucm-ivn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teucm-ivn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:caret-down-outline" /></template>
