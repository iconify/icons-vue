<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq2m00b2g.css';
import '../../css/a/a6rvn_b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq2m00b2g"/><path class="a6rvn_b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-copy-alt" /></template>
