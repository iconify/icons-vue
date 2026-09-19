<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw6az9bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw6az9bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-jpg" /></template>
