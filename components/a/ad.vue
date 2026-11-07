<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajg2r_b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajg2r_b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:ad" /></template>
