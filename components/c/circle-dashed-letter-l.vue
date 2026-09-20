<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb9fzlbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb9fzlbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-l" /></template>
