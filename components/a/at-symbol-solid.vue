<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwy9wwbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwy9wwbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:at-symbol-solid" /></template>
