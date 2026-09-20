<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5i5cv5sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5i5cv5sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-minus" /></template>
