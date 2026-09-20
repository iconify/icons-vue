<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2-ygo_xi.css';
import '../../css/j/j3loqwvbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2-ygo_xi"/><path class="j3loqwvbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:earpods-ear-bold" /></template>
