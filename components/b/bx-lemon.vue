<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn_saxb8w.css';
import '../../css/b/bkpxyzsbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn_saxb8w"/><path class="bkpxyzsbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-lemon" /></template>
