<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kax5-cj7n.css';
import '../../css/m/mk5ucybgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kax5-cj7n"/><path clip-rule="evenodd" class="mk5ucybgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:drama-filled" /></template>
