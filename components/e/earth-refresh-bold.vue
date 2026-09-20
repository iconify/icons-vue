<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob991ac-v.css';
import '../../css/l/lbnegcbec.css';
import '../../css/v/vneknnfuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob991ac-v"/><path class="lbnegcbec"/><path class="vneknnfuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:earth-refresh-bold" /></template>
