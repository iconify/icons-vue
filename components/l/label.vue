<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rey4ck1nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rey4ck1nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:label" /></template>
