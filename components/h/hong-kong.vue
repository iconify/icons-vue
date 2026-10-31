<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dki-1w-8i.css';
import '../../css/s/s1c8xvkzj.css';
import '../../css/i/iq_z596tt.css';
import '../../css/y/y1n_k57xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="dki-1w-8i"/><path class="s1c8xvkzj"/><path class="iq_z596tt"/><path class="y1n_k57xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:hong-kong" /></template>
