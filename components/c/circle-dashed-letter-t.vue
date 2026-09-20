<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvp-9fuxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvp-9fuxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-t" /></template>
