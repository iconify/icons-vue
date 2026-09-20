<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc7ztv3im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kc7ztv3im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:behance-original" /></template>
