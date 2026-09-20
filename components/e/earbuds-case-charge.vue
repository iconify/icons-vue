<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw569bbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nw569bbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earbuds-case-charge" /></template>
