<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agnqmmhmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agnqmmhmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-cny-line" /></template>
