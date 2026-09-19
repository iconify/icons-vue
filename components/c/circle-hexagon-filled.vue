<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crmgxgsvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b crmgxgsvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-hexagon-filled" /></template>
