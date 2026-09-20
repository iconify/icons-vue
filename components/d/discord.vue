<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rokjod_3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rokjod_3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:discord" /></template>
