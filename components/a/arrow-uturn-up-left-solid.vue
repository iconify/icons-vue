<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmoot56zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmoot56zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-up-left-solid" /></template>
