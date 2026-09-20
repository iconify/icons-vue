<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akkbdcc0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akkbdcc0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:component-layout-filled" /></template>
