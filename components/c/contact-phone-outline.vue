<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb9u09bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb9u09bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:contact-phone-outline" /></template>
