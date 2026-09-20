<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngwhen9gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngwhen9gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apm-terminals" /></template>
