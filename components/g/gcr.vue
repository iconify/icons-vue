<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8z545b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8z545b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gcr" /></template>
