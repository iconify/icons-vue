<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqytxs1ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqytxs1ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-key" /></template>
