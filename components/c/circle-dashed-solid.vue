<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf54j2bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zf54j2bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-dashed-solid" /></template>
