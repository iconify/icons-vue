<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7w121h3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7w121h3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency" /></template>
