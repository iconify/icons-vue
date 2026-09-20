<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjvvu4-to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjvvu4-to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:crown-a" /></template>
