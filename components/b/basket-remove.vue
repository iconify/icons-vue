<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs88hfbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs88hfbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:basket-remove" /></template>
