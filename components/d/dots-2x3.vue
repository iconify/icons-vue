<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_zvwqk6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_zvwqk6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x3" /></template>
