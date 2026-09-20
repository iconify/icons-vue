<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wayg92b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wayg92b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:facebook-original" /></template>
