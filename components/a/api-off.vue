<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5klrkbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5klrkbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:api-off" /></template>
