<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umcxplilb.css';
import '../../css/r/r2vwgjbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umcxplilb"/><path class="r2vwgjbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dam-4-filled" /></template>
