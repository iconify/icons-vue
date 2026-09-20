<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e34wibc1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e34wibc1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:justgiving" /></template>
