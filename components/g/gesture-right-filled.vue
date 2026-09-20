<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijmewwb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijmewwb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-right-filled" /></template>
