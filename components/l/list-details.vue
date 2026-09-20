<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aay81scoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aay81scoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:list-details" /></template>
