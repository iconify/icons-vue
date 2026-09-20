<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbwvucc5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbwvucc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-spacing" /></template>
