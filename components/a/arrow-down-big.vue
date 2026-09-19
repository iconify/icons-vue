<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk0is-bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk0is-bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-big" /></template>
