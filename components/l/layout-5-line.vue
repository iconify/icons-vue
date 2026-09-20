<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkmcx94uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkmcx94uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-5-line" /></template>
