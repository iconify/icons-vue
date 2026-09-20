<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjhypr_5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gjhypr_5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:formula" /></template>
