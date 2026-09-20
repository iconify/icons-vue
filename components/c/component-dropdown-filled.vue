<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/squnycb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="squnycb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:component-dropdown-filled" /></template>
