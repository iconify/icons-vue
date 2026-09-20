<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smxvd6p6i.css';
import '../../css/p/pe_k9tbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smxvd6p6i"/><path class="pe_k9tbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:launch" /></template>
