<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ust7zubzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ust7zubzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-z" /></template>
