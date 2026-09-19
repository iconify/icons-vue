<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bot9nzqtg.css';
import '../../css/o/o04p_sbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bot9nzqtg"/><path class="o04p_sbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-square-half-filled" /></template>
