<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o86j1obkt.css';
import '../../css/s/splrb5bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o86j1obkt"/><path class="splrb5bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:collection" /></template>
