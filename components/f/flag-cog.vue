<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/one-8ebop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="one-8ebop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-cog" /></template>
