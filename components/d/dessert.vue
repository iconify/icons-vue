<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iap_x96bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iap_x96bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dessert" /></template>
