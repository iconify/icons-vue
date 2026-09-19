<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3tspm3_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3tspm3_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:deviantart" /></template>
