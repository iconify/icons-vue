<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gteaiobyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gteaiobyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:left-indent" /></template>
