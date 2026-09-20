<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsnw-kpoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsnw-kpoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bs" /></template>
