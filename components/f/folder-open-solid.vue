<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frlhmob0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frlhmob0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-open-solid" /></template>
