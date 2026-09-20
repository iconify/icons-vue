<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqx3m-pme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqx3m-pme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-arrow-up-filled" /></template>
