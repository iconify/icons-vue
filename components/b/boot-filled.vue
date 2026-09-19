<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm-8qacrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm-8qacrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:boot-filled" /></template>
