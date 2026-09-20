<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q23succzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q23succzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bounce-left" /></template>
