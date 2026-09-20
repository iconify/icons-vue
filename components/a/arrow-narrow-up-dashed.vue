<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igrvd-boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igrvd-boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-narrow-up-dashed" /></template>
