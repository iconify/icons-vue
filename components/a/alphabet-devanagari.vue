<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyeq4tbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyeq4tbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alphabet-devanagari" /></template>
