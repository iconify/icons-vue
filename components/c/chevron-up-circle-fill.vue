<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzpxb50ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzpxb50ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chevron-up-circle-fill" /></template>
