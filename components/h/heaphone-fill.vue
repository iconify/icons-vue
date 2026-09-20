<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjj35evch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjj35evch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:heaphone-fill" /></template>
