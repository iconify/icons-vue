<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4xr0yhpn.css';
import '../../css/f/f2h708bjp.css';
import '../../css/c/c0k_mybxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4xr0yhpn"/><path class="f2h708bjp"/><path class="c0k_mybxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-1-filled" /></template>
