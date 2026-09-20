<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0lb7jblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0lb7jblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:black-hole2" /></template>
