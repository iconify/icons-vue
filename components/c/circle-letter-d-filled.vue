<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi7p1wbtw.css';
import '../../css/w/w5e400bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi7p1wbtw"/><path clip-rule="evenodd" class="w5e400bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-d-filled" /></template>
