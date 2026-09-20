<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na4d8xgib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na4d8xgib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:aeromexico" /></template>
