<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8d5efrig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t8d5efrig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cabinet-filled" /></template>
