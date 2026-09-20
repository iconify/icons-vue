<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xktlhq9bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xktlhq9bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:error-404" /></template>
