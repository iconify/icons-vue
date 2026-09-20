<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yweuki_xe.css';
import '../../css/b/biljftzdn.css';
import '../../css/x/x56wbk0pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yweuki_xe"/><path class="biljftzdn"/><path clip-rule="evenodd" class="x56wbk0pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:burger-duotone" /></template>
