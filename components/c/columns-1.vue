<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g30ii7bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g30ii7bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:columns-1" /></template>
