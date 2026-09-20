<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd7j-wizo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd7j-wizo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:join-round" /></template>
