<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9mo31emm.css';
import '../../css/y/ysrry-bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9mo31emm"/><path class="ysrry-bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-up-right-circle" /></template>
