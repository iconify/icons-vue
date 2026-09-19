<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuchegb-g.css';
import '../../css/i/izub48k_p.css';
import '../../css/q/qnwimlb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuchegb-g"/><path class="izub48k_p"/><path class="qnwimlb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bear" /></template>
