<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlrg2jwsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlrg2jwsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-left-fill" /></template>
