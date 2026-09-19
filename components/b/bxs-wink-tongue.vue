<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pstg2i40z.css';
import '../../css/r/r3j7g_mer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pstg2i40z"/><path class="r3j7g_mer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-wink-tongue" /></template>
