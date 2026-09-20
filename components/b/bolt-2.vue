<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqzxq_bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="bqzxq_bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bolt-2" /></template>
