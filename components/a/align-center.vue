<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6py-t-qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6py-t-qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:align-center" /></template>
