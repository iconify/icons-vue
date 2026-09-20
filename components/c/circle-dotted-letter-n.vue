<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czi_pacop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czi_pacop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-n" /></template>
