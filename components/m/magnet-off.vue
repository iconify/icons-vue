<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_-3yab7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_-3yab7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:magnet-off" /></template>
