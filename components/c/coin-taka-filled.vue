<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdj-y3bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdj-y3bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:coin-taka-filled" /></template>
