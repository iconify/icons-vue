<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgafo662c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lgafo662c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:badoo-logo-solid" /></template>
