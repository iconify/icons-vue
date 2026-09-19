<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onw5m771l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="onw5m771l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:info-triangle-solid" /></template>
