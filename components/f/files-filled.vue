<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc85bcglw.css';
import '../../css/s/slcvs4yrl.css';
import '../../css/g/gdfre-uew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc85bcglw"/><path class="slcvs4yrl"/><path class="gdfre-uew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:files-filled" /></template>
