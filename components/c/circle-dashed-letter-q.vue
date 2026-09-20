<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwdd_rbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwdd_rbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-q" /></template>
