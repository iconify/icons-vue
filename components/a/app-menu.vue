<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl8zml4wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl8zml4wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:app-menu" /></template>
