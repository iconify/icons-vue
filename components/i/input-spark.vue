<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj4cqpcwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj4cqpcwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:input-spark" /></template>
