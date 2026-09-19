<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djv6i7b0m.css';
import '../../css/j/jf_6np9ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="djv6i7b0m"/><path class="jf_6np9ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-hotel" /></template>
