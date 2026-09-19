<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiu_6cclx.css';
import '../../css/k/kc82gybja.css';
import '../../css/l/l2xkgdcaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiu_6cclx"/><rect class="kc82gybja"/><rect class="l2xkgdcaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:between-vertical-start-filled" /></template>
