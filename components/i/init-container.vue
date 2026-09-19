<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5tcmf-xm.css';
import '../../css/w/wo40o9c3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5tcmf-xm"/><path class="wo40o9c3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:init-container" /></template>
