<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icwuntb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="icwuntb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chart-line-up-solid" /></template>
