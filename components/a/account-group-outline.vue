<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfli58bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfli58bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-group-outline" /></template>
