<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr37rf74y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr37rf74y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:luggage" /></template>
