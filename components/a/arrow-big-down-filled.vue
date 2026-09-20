<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahikm_xfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahikm_xfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-down-filled" /></template>
