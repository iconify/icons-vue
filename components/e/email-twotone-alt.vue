<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmpqyqiqj.css';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h8nrrffsv.css';
import '../../css/j/j92lilcpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path fill-opacity="0" class="nmpqyqiqj"><animate fill="freeze" attributeName="fill-opacity" begin="0.9s" dur="0.15s" to=".3"/></path><g class="nrj6p8qat"><path class="h8nrrffsv"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.6s" values="66;0"/></path><path stroke-dashoffset="24" class="j92lilcpo"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.6s" dur="0.3s" to="0"/></path></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:email-twotone-alt" /></template>
