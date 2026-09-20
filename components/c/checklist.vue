<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d22wuprbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d22wuprbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:checklist" /></template>
