<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxw36h-hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxw36h-hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-male" /></template>
