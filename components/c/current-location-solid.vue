<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pejqq1mje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pejqq1mje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:current-location-solid" /></template>
