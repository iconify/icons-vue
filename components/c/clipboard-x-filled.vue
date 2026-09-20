<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvx85gb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvx85gb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clipboard-x-filled" /></template>
