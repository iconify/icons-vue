<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlue2nbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlue2nbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-hail-solid" /></template>
