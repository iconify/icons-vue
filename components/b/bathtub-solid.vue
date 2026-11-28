<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vujq3pbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vujq3pbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bathtub-solid" /></template>
