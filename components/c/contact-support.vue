<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exleob20c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="exleob20c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contact-support" /></template>
