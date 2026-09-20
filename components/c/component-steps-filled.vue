<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhd2yph4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhd2yph4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:component-steps-filled" /></template>
