<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-spu3__s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-spu3__s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:cloud-off" /></template>
