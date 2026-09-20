<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjiukf_9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjiukf_9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bed-off" /></template>
