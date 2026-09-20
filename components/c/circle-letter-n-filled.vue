<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1b637mci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1b637mci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-n-filled" /></template>
