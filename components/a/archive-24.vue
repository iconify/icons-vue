<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0a_25-9h.css';
import '../../css/m/mfxe6gbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0a_25-9h"/><path class="mfxe6gbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:archive-24" /></template>
