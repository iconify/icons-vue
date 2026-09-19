<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bikzi3bkv.css';
import '../../css/l/l-d0mzbnh.css';
import '../../css/v/v45s4tbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bikzi3bkv"/><path class="l-d0mzbnh"/><path class="v45s4tbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:hearing-aid" /></template>
