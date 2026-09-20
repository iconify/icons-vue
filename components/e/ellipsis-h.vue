<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty_ooxbvp.css';
import '../../css/f/ffappobrr.css';
import '../../css/u/uzprxqbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ty_ooxbvp"/><circle class="ffappobrr"/><circle class="uzprxqbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:ellipsis-h" /></template>
