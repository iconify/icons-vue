<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxrmtyu_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxrmtyu_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-chevron-right-fill" /></template>
