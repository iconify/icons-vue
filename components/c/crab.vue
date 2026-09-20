<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfa1bh-8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfa1bh-8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:crab" /></template>
