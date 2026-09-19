<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqwr_sfrm.css';
import '../../css/i/i6wr-kbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqwr_sfrm"/><path class="i6wr-kbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:lock-outline" /></template>
