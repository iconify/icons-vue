<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-1o1p8mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-1o1p8mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:edit-alt" /></template>
