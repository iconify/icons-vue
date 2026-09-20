<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idsrdcruo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idsrdcruo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right2-filled" /></template>
