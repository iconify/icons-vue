<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg_nm4bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg_nm4bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:link-exclamation" /></template>
