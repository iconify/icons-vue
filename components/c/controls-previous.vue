<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0du4vb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0du4vb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:controls-previous" /></template>
