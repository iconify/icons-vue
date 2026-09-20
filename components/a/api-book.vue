<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abjm_pc7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abjm_pc7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:api-book" /></template>
