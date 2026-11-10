<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr52k_9za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cr52k_9za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-check-solid" /></template>
