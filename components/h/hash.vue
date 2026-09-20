<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy5kwhgdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy5kwhgdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:hash" /></template>
