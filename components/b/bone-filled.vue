<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esm08ypvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esm08ypvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bone-filled" /></template>
