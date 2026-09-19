<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9goa4bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g9goa4bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-arrow-down-solid" /></template>
