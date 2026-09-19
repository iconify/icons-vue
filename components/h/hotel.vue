<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afvdaibxt.css';
import '../../css/w/wfvxprbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="afvdaibxt"/><path class="wfvxprbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:hotel" /></template>
