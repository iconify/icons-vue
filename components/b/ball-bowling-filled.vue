<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paf7bkbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paf7bkbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ball-bowling-filled" /></template>
