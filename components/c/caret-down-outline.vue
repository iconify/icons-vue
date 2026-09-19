<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezwqmabwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezwqmabwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:caret-down-outline" /></template>
