<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8dcpqbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8dcpqbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-expand-right" /></template>
