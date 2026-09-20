<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph7wxybju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ph7wxybju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:insert-top-left-solid" /></template>
