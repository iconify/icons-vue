<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp81k8bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rp81k8bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-outline" /></template>
