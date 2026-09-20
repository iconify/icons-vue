<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0l4_3bke.css';
import '../../css/d/d01f2_1py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0l4_3bke"/><path class="d01f2_1py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cello-24" /></template>
