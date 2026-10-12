<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm3xqsybe.css';
import '../../css/q/qf40r3s6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rm3xqsybe"/><path class="qf40r3s6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-plus-filled" /></template>
