<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzgfacbmm.css';
import '../../css/j/jci34lbfa.css';
import '../../css/v/vrhyijbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzgfacbmm"/><path class="jci34lbfa"/><path class="vrhyijbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:book-open" /></template>
