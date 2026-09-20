<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkufy8bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkufy8bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrows-all-direction-2" /></template>
