<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j__y33b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j__y33b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gymnastics" /></template>
