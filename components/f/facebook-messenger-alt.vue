<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px1bfwbyg.css';
import '../../css/x/xblgcabps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px1bfwbyg"/><path class="xblgcabps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:facebook-messenger-alt" /></template>
