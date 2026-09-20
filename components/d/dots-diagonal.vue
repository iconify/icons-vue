<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-8zq7ywg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-8zq7ywg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dots-diagonal" /></template>
