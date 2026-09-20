<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpbl5f9pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpbl5f9pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-minus" /></template>
