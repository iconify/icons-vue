<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm498ybdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm498ybdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-left-sharp" /></template>
