<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgch26bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgch26bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bell-snooze-solid" /></template>
