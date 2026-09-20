<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c47r4ib7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c47r4ib7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-upload-outline" /></template>
