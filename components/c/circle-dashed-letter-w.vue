<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z860pctsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z860pctsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-w" /></template>
