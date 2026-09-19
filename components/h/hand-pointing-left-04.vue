<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aer23ob0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aer23ob0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-pointing-left-04" /></template>
