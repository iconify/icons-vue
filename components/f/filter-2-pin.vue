<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/but20cbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="but20cbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-pin" /></template>
