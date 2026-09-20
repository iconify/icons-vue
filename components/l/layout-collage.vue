<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3dd6fu-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3dd6fu-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-collage" /></template>
