<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn_frcb-c.css';
import '../../css/i/i_cgi-t8l.css';
import '../../css/h/hj4ovvz1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_frcb-c"/><path class="i_cgi-t8l"/><path clip-rule="evenodd" class="hj4ovvz1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-square-bold-duotone" /></template>
