<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pww4j9bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pww4j9bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:archive-drawer-fill" /></template>
