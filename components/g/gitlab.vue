<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmnc_7bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmnc_7bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:gitlab" /></template>
