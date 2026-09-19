<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r70k8h0fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r70k8h0fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-management" /></template>
