<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibohz8bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibohz8bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-left-down-solid" /></template>
