<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vla37tbfm.css';
import '../../css/v/vhe-a2h2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vla37tbfm"/><path class="vhe-a2h2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-alert-duotone" /></template>
