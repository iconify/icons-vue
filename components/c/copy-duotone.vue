<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbjam7ssf.css';
import '../../css/h/h-k00lbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbjam7ssf"/><path class="h-k00lbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:copy-duotone" /></template>
