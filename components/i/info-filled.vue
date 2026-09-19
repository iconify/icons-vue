<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suvk3db8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="suvk3db8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:info-filled" /></template>
