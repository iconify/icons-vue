<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-p0pgp4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-p0pgp4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chevron-up" /></template>
