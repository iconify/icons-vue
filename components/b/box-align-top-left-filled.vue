<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqb5wb4we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqb5wb4we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-top-left-filled" /></template>
