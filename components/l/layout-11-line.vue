<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb5e2cbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb5e2cbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-11-line" /></template>
