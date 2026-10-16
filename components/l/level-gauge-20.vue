<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6huerbpx.css';
import '../../css/l/li94czbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b6huerbpx"/><path class="li94czbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:level-gauge-20" /></template>
