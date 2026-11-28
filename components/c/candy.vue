<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq-kfj9bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq-kfj9bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:candy" /></template>
