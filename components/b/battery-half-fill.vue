<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm-cbjo0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm-cbjo0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:battery-half-fill" /></template>
