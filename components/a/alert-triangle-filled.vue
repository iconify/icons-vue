<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxkhv8bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxkhv8bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alert-triangle-filled" /></template>
