<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkmfunbhg.css';
import '../../css/f/fvf990b7v.css';
import '../../css/b/bbacmnblc.css';
import '../../css/n/n5eo0ek4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkmfunbhg wm-a"/><path class="fvf990b7v wm-k"/><path class="bbacmnblc wm-a"/><path class="n5eo0ek4e wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:battery" /></template>
