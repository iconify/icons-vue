<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4_xreixv.css';
import '../../css/t/te4hkcb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4_xreixv"/><path class="te4hkcb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-moved-24" /></template>
