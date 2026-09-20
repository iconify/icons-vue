<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6yffcy2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6yffcy2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:kai-os-logo-solid" /></template>
