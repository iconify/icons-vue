<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1kthrdrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1kthrdrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down-3-filled" /></template>
