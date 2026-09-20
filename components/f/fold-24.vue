<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-kcmxnus.css';
import '../../css/p/pm72mougk.css';
import '../../css/l/l7j3nibvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-kcmxnus"/><path class="pm72mougk"/><path class="l7j3nibvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fold-24" /></template>
