<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxy1tsrmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxy1tsrmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-star" /></template>
