<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cag813bfc.css';
import '../../css/g/givljsy1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cag813bfc"/><path class="givljsy1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-cross-filled" /></template>
