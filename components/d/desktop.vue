<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smm_-b_wm.css';
import '../../css/d/dzs_rab9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smm_-b_wm"/><path class="dzs_rab9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:desktop" /></template>
