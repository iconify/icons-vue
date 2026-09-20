<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx1irjf6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx1irjf6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-upload-fill" /></template>
