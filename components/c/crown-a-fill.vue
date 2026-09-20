<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbv-3pwvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbv-3pwvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:crown-a-fill" /></template>
