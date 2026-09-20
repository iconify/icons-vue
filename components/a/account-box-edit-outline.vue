<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-2-zob9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-2-zob9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-box-edit-outline" /></template>
