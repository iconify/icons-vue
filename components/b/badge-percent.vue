<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evm-pg59v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evm-pg59v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:badge-percent" /></template>
