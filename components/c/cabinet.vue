<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8g3j-b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8g3j-b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cabinet" /></template>
