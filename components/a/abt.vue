<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq06-391u.css';
import '../../css/r/rte4cibeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yq06-391u"/><path class="rte4cibeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:abt" /></template>
