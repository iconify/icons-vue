<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z126c-1nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z126c-1nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lg" /></template>
