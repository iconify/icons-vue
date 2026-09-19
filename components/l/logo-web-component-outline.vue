<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4c8pd5le.css';
import '../../css/c/clgeaqb1x.css';
import '../../css/y/yq8uffbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4c8pd5le"/><path class="clgeaqb1x"/><path class="yq8uffbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-web-component-outline" /></template>
