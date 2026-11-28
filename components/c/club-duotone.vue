<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx1599bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary tx1599bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:club-duotone" /></template>
