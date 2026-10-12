<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u52a-ibck.css';
import '../../css/j/jhwn4fbsd.css';
import '../../css/q/qmmb_82ud.css';
import '../../css/u/ui-ddfl2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u52a-ibck"/><path class="jhwn4fbsd"/><path class="qmmb_82ud"/><path class="ui-ddfl2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charger-off-20-bold" /></template>
