<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x15qracvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x15qracvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:chevron-up" /></template>
