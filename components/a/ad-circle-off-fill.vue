<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsmsgz_jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsmsgz_jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-circle-off-fill" /></template>
