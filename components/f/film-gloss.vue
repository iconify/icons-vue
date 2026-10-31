<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u01oaubiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u01oaubiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:film-gloss" /></template>
