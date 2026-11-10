<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb-md8jcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-md8jcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:gift" /></template>
