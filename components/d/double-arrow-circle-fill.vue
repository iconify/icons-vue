<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb9q0o-di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb9q0o-di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:double-arrow-circle-fill" /></template>
