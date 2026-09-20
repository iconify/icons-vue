<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iflla3gmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iflla3gmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-frown-fill" /></template>
