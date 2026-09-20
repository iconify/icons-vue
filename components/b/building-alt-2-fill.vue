<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyq5_6mmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyq5_6mmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:building-alt-2-fill" /></template>
