<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coe7vibui.css';
import '../../css/u/ud8fztbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coe7vibui"/><path clip-rule="evenodd" class="ud8fztbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-ring-outline" /></template>
