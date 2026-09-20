<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t40090bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t40090bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lego-filled" /></template>
