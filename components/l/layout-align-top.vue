<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlrjk96mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlrjk96mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-align-top" /></template>
