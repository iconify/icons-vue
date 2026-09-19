<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9g34html.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9g34html"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceska-posta" /></template>
