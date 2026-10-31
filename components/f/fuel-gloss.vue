<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbt_36vsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbt_36vsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fuel-gloss" /></template>
