<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlmbm6brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlmbm6brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-share" /></template>
