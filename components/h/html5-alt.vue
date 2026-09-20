<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llko29bid.css';
import '../../css/a/a9_rmzbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llko29bid"/><path class="a9_rmzbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:html5-alt" /></template>
