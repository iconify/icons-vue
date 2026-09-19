<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiy8pp_yv.css';
import '../../css/b/b2m7ke2wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiy8pp_yv"/><path class="b2m7ke2wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:conversation" /></template>
