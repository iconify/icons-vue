<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fctujlv1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="fctujlv1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-right-left-26" /></template>
