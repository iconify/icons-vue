<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgd8bzbml.css';
import '../../css/q/qfm_mp96p.css';
import '../../css/c/cm457dbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgd8bzbml"/><path class="qfm_mp96p"/><path class="cm457dbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-left-bold-duotone" /></template>
