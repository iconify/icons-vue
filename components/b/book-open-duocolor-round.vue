<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcujul4wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcujul4wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open-duocolor-round" /></template>
