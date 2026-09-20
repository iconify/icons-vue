<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otaqqnb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="otaqqnb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:dailybooth-logo-solid" /></template>
