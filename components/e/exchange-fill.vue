<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9m30gb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9m30gb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:exchange-fill" /></template>
