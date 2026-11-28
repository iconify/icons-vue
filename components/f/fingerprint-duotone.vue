<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yggk-nx0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yggk-nx0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:fingerprint-duotone" /></template>
