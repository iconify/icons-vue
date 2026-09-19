<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxpmqvbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxpmqvbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrange-by-numbers-91" /></template>
