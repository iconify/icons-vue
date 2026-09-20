<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peci-0buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peci-0buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:high-level-filled" /></template>
