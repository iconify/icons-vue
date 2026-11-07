<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln1f_4blw.css';
import '../../css/u/u8s4_onzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln1f_4blw"/><path class="u8s4_onzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-bold-duotone" /></template>
