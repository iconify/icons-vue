<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfyw0bf2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfyw0bf2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:capture-filled" /></template>
