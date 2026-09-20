<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzbgp2w2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzbgp2w2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cookie" /></template>
