<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvi020bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvi020bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:database-solid" /></template>
