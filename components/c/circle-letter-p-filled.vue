<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eocas0q3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eocas0q3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-p-filled" /></template>
