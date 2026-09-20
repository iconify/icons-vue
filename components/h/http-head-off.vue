<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3spu_4jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3spu_4jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-head-off" /></template>
