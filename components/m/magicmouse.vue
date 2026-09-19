<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzkh3bczm.css';
import '../../css/k/kic1kiyda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="qzkh3bczm"/><circle class="kic1kiyda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:magicmouse" /></template>
