<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_auzoz_p.css';
import '../../css/a/a4u_2wblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_auzoz_p"/><path class="a4u_2wblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-crop" /></template>
