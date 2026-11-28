<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx_mtm98y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary tx_mtm98y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-duotone" /></template>
