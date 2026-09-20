<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olc3e_b1f.css';
import '../../css/x/xdvj_qs2e.css';
import '../../css/l/lv0o3p4mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="olc3e_b1f"/><path class="xdvj_qs2e"/><path class="lv0o3p4mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-poll" /></template>
