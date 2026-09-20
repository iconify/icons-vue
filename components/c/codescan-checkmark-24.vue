<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnken7bpp.css';
import '../../css/p/pbgwgktza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnken7bpp"/><path class="pbgwgktza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:codescan-checkmark-24" /></template>
