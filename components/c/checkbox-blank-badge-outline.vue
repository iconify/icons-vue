<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3rimeb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3rimeb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkbox-blank-badge-outline" /></template>
