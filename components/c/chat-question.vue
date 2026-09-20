<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h_5yx_b2v.css';
import '../../css/w/wu23-3bwn.css';
import '../../css/o/obkdnvb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h_5yx_b2v"/><path class="wu23-3bwn"/><circle class="obkdnvb0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:chat-question" /></template>
