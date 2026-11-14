<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7lxfp4gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7lxfp4gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-02" /></template>
