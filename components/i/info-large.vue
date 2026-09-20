<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d37zg4ilz.css';
import '../../css/f/fe11hu57u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d37zg4ilz"/><circle class="fe11hu57u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:info-large" /></template>
