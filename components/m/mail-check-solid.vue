<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr0-7kx7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr0-7kx7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-check-solid" /></template>
