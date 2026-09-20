<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrsuk5b6z.css';
import '../../css/s/s_3yk55iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrsuk5b6z"/><path class="s_3yk55iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bling-line" /></template>
