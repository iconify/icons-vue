<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jui78c6qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jui78c6qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chevron-left-circle-fill" /></template>
