<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pghs5ubcb.css';
import '../../css/k/kuvw34acp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pghs5ubcb"/><path class="kuvw34acp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:function-20" /></template>
