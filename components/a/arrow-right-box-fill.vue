<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msx5hkgzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msx5hkgzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-box-fill" /></template>
