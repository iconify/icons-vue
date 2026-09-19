<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9hx4balk.css';
import '../../css/g/gx74lwb0e.css';
import '../../css/b/b3v177x2s.css';
import '../../css/n/n0ij7acao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a9hx4balk"/><path class="gx74lwb0e"/><path class="b3v177x2s"/><path class="n0ij7acao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:levels" /></template>
