<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya-kp0bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya-kp0bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:lightning-2-fill" /></template>
