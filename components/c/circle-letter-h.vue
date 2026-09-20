<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm19ivbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm19ivbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-h" /></template>
