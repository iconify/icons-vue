<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnm9yk__a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnm9yk__a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:download-sharp-fill" /></template>
