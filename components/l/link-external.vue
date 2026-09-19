<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvi6kbbfc.css';
import '../../css/a/aueya6btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvi6kbbfc"/><path class="aueya6btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:link-external" /></template>
