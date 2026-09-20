<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnf55gbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnf55gbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-fill" /></template>
