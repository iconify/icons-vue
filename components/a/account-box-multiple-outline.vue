<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnmw1ju5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnmw1ju5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-box-multiple-outline" /></template>
