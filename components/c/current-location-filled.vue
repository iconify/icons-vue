<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxq3jkbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxq3jkbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:current-location-filled" /></template>
