<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbtvdn1tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbtvdn1tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-flame" /></template>
