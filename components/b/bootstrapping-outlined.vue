<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh10aeonn.css';
import '../../css/t/t08gpvbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh10aeonn"/><path class="t08gpvbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:bootstrapping-outlined" /></template>
