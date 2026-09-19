<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxl64k79c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxl64k79c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:email-open-alt" /></template>
