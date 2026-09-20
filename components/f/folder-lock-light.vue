<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udtztp8ns.css';
import '../../css/w/wc5zi-5ib.css';
import '../../css/n/nlwj_sxhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udtztp8ns"/><path clip-rule="evenodd" class="wc5zi-5ib"/><path clip-rule="evenodd" class="nlwj_sxhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-lock-light" /></template>
