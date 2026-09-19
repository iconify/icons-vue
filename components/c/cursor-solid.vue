<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbk37tb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbk37tb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cursor-solid" /></template>
