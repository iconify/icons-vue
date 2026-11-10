<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/www7zt58m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="www7zt58m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-exclamation-solid" /></template>
