<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcgn2-byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xcgn2-byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:logo-android-text" /></template>
