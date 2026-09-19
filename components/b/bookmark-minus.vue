<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9jq5ybcb.css';
import '../../css/b/bxmkebcbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9jq5ybcb"/><path class="bxmkebcbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-minus" /></template>
