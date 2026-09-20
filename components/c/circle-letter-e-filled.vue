<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlj__gane.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlj__gane"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-e-filled" /></template>
