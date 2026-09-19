<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tco8mq__i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tco8mq__i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bank-filled" /></template>
