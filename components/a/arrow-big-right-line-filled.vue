<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkmq3hkqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkmq3hkqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-right-line-filled" /></template>
