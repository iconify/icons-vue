<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of7chwb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of7chwb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-f" /></template>
