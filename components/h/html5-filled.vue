<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsh2eobjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsh2eobjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:html5-filled" /></template>
