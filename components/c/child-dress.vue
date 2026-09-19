<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q--rc_bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="q--rc_bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:child-dress" /></template>
