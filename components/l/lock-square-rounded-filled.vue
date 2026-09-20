<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i131zj91m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i131zj91m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lock-square-rounded-filled" /></template>
