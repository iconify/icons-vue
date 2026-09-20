<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beld5sdfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beld5sdfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ban-2" /></template>
