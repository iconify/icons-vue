<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iihzdhrri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iihzdhrri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x3" /></template>
