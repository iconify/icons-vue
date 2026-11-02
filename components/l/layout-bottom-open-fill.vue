<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utprw0bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utprw0bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-bottom-open-fill" /></template>
