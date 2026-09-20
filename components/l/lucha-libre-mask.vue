<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3zsixb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k3zsixb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lucha-libre-mask" /></template>
