<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3cx9kfqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3cx9kfqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:honey-02" /></template>
