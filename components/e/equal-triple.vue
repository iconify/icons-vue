<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aosgu1bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aosgu1bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:equal-triple" /></template>
