<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7vb09_my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7vb09_my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:external-link" /></template>
