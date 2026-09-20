<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzz54ue_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bzz54ue_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-turn-down-large-solid" /></template>
