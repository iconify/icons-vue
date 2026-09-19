<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sebtdl11v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sebtdl11v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-up-right" /></template>
