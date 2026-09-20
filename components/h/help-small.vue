<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyrvqk-2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyrvqk-2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:help-small" /></template>
