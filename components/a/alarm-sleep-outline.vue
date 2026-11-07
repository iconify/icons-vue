<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzp1lwttm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bzp1lwttm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alarm-sleep-outline" /></template>
