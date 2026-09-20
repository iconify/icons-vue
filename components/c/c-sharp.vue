<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovc2j_bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovc2j_bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:c-sharp" /></template>
