<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhimr1abp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hhimr1abp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-case-charge-outline" /></template>
