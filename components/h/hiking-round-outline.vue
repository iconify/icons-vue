<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2c1ynjwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2c1ynjwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-round-outline" /></template>
