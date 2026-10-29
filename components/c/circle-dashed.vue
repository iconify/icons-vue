<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-hg0bczz.css';
import '../../css/n/ncl94fqvy.css';
import '../../css/n/nndd3wbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-hg0bczz wm-shadow"/><path class="ncl94fqvy wm-k"/><path class="nndd3wbqy wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:circle-dashed" /></template>
