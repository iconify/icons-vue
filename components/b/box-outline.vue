<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmhjqwmsl.css';
import '../../css/r/r56ofqbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmhjqwmsl"/><path clip-rule="evenodd" class="r56ofqbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:box-outline" /></template>
