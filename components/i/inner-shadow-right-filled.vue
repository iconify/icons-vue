<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re2_yqpfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re2_yqpfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:inner-shadow-right-filled" /></template>
