<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9a-vzbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9a-vzbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-pointing-right-04" /></template>
