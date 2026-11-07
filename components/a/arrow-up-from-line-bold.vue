<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm2cgjbbr.css';
import '../../css/v/vh0_98nmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm2cgjbbr"/><path class="vh0_98nmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-from-line-bold" /></template>
