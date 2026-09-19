<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7slzmblf.css';
import '../../css/y/ywurx5bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q7slzmblf"/><path class="ywurx5bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:eye-off" /></template>
