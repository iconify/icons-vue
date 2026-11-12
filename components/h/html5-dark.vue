<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm81rxbus.css';
import '../../css/a/at75z3hdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lm81rxbus"/><path class="at75z3hdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:html5-dark" /></template>
