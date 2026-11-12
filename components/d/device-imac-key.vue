<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adv3nryks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adv3nryks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-key" /></template>
