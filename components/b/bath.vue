<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st9q2dp3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st9q2dp3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bath" /></template>
