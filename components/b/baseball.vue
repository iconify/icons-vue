<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc-ua0jey.css';
import '../../css/j/jdy3hm0zi.css';
import '../../css/m/m18nddcif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kc-ua0jey"/><path class="jdy3hm0zi"/><path class="m18nddcif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:baseball" /></template>
