<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk3jmra7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk3jmra7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chair-director" /></template>
