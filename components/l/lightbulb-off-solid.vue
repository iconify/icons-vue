<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfnuo7ojb.css';
import '../../css/t/tmkl2dpkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfnuo7ojb"/><path class="tmkl2dpkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:lightbulb-off-solid" /></template>
