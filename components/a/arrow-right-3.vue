<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zshw9xbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zshw9xbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right-3" /></template>
