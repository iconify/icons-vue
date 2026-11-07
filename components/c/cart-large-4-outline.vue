<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el_6s4qrm.css';
import '../../css/d/dnt469bqu.css';
import '../../css/b/bmgyaxqnm.css';
import '../../css/i/i4d0c09qh.css';
import '../../css/b/bypq3rbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el_6s4qrm"/><path class="dnt469bqu"/><path clip-rule="evenodd" class="bmgyaxqnm"/><path clip-rule="evenodd" class="i4d0c09qh"/><path clip-rule="evenodd" class="bypq3rbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-large-4-outline" /></template>
