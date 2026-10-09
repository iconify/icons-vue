<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8lb6scap.css';
import '../../css/j/j31r41azg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z8lb6scap"/><path class="j31r41azg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dispatch-20" /></template>
