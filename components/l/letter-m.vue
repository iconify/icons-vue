<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeze8yeqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeze8yeqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-m" /></template>
