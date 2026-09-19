<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnf2tkbyn.css';
import '../../css/w/wu0j47nvj.css';
import '../../css/x/x2cdf-bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnf2tkbyn"/><path class="wu0j47nvj"/><path class="x2cdf-bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bandage" /></template>
