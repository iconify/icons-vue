<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch0jmzcyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch0jmzcyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:expand-outline" /></template>
