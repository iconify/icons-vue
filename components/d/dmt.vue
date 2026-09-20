<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-f8k3blw.css';
import '../../css/a/a4zhphb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-f8k3blw"/><path class="a4zhphb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dmt" /></template>
