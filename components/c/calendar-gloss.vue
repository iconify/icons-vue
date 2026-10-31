<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b94hs4mrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b94hs4mrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-gloss" /></template>
