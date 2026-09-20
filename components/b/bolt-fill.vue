<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg_ed7b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_ed7b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bolt-fill" /></template>
