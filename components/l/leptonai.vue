<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evd8kfjws.css';
import '../../css/h/hxci04b3v.css';
import '../../css/w/wrzgswrqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="evd8kfjws"/><path clip-rule="evenodd" class="hxci04b3v"/><path class="wrzgswrqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:leptonai" /></template>
