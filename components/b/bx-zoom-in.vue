<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d73-y3xmt.css';
import '../../css/y/yk_rn_urw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d73-y3xmt"/><path class="yk_rn_urw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-zoom-in" /></template>
