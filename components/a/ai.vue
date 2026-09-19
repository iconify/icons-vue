<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci71hn2_l.css';
import '../../css/a/ae5r06sbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci71hn2_l"/><path class="ae5r06sbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:ai" /></template>
