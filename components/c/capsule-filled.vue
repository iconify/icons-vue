<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne9la_bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne9la_bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:capsule-filled" /></template>
