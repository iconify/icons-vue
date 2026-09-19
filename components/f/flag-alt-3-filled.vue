<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak6-xi64q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak6-xi64q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flag-alt-3-filled" /></template>
