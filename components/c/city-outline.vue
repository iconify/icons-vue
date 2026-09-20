<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktsidi8ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktsidi8ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:city-outline" /></template>
