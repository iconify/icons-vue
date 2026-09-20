<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e64zmbcca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e64zmbcca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:contrast-filled" /></template>
