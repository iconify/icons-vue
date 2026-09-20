<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cebdwg14u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cebdwg14u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:clean-broom-wipe-remix" /></template>
