<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4aexd1cu.css';
import '../../css/k/kpl5dzvml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4aexd1cu"/><path class="kpl5dzvml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-cat" /></template>
