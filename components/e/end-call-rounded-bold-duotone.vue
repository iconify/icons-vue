<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd7n-fdmu.css';
import '../../css/t/tkkwlub3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zd7n-fdmu"/><path class="tkkwlub3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-rounded-bold-duotone" /></template>
