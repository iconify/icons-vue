<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh26h9acs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh26h9acs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-clock-solid" /></template>
