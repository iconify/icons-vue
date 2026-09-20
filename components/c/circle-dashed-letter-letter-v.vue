<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4ztmjbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4ztmjbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-letter-v" /></template>
