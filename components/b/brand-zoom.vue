<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoeg_kxij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoeg_kxij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-zoom" /></template>
