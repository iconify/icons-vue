<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tzy_pd90l.css';
import '../../css/u/ua78apbcf.css';
import '../../css/f/fjm43zboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tzy_pd90l"/><path class="ua78apbcf"/><path class="fjm43zboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:ai-edit-robot-flat" /></template>
