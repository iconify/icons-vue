<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j95h7gbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j95h7gbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cell-signal-5" /></template>
