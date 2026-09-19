<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a91t2_tvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":850};
const content = `<path class="a91t2_tvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:dropbox" /></template>
