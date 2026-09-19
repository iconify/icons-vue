<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8qh8v6xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8qh8v6xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:island" /></template>
