<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfbtap09s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfbtap09s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:layout" /></template>
