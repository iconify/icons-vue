<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-7p1xbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-7p1xbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-raised" /></template>
