<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nijwh4svl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nijwh4svl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-koala-gloss" /></template>
