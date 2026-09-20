<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwn92wljf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwn92wljf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:key-off" /></template>
