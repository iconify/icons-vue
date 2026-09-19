<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btx7j3qro.css';
import '../../css/l/l_uqpac8o.css';
import '../../css/q/qwjmiebxi.css';
import '../../css/f/fqv6mgkqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="btx7j3qro"/><path class="l_uqpac8o"/><path class="qwjmiebxi"/><path class="fqv6mgkqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:fileaudio" /></template>
