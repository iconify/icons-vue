<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzg-lx-zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzg-lx-zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-a-filled" /></template>
