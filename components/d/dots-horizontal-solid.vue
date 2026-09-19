<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9bzb7gtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9bzb7gtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:dots-horizontal-solid" /></template>
