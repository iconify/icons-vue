<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2vvmdmrt.css';
import '../../css/k/knuihczfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2vvmdmrt"/><path class="knuihczfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-alert-solid" /></template>
