<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag5tnvbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag5tnvbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-right-circle-filled" /></template>
