<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm81rxbus.css';
import '../../css/o/otjlhglbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lm81rxbus"/><path class="otjlhglbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:html5-dark" /></template>
