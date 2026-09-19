<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzuusgytb.css';
import '../../css/t/t_wx_r-8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzuusgytb"/><path class="t_wx_r-8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-user-voice" /></template>
