<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw4s_ccdv.css';
import '../../css/a/afxn0v40s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="pw4s_ccdv"/><path class="afxn0v40s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:angle-double-down" /></template>
